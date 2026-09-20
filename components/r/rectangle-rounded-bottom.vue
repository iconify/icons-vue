<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rifrj-b7a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rifrj-b7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:rectangle-rounded-bottom" /></template>
