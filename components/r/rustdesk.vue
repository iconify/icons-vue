<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ic99fny_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ic99fny_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:rustdesk" /></template>
