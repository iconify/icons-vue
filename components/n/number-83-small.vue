<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ui_95wbws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ui_95wbws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:number-83-small" /></template>
