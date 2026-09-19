<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mae29i7lc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mae29i7lc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:paragraph" /></template>
