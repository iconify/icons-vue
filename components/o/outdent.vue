<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kdsuibblv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kdsuibblv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:outdent" /></template>
