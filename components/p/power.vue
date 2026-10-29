<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nl72jlb_c.css';
import '../../css/n/n6ltouozm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nl72jlb_c"/><path class="n6ltouozm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:power" /></template>
