<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iytak3z-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iytak3z-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:smile-dizzy" /></template>
