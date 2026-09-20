<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ghyd-h94s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ghyd-h94s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:trending-up-down-solid" /></template>
