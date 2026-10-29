<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ec5wflrnp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ec5wflrnp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:navigation-2-solid" /></template>
