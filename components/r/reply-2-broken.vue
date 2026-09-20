<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y7l4j2u2p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y7l4j2u2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:reply-2-broken" /></template>
