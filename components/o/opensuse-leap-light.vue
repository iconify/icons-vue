<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/ja_hni21a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ja_hni21a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:opensuse-leap-light" /></template>
