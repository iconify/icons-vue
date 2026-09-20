<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lwa2__bso.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lwa2__bso"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:upload" /></template>
