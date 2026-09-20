<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gmmlnjhhv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gmmlnjhhv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:remove-square-line" /></template>
