<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/smhe7gbkt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="smhe7gbkt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:table-filled" /></template>
