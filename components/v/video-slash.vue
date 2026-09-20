<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g9gxfgg1g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g9gxfgg1g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:video-slash" /></template>
