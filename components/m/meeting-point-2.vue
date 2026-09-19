<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ma4g31zac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ma4g31zac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:meeting-point-2" /></template>
