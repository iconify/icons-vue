<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oaizi48jf.css';
import '../../css/k/knuimbb4q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oaizi48jf"/><path class="knuimbb4q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:shield-star-bold-duotone" /></template>
