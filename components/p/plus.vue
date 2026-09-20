<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ug6dl0bdc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ug6dl0bdc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:plus" /></template>
