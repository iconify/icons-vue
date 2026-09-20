<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ilbmb7yhg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ilbmb7yhg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:phone-hang-up" /></template>
