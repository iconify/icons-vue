<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bfaggn45q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bfaggn45q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:shapes" /></template>
