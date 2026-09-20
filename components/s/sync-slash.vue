<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eu862bcaz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eu862bcaz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:sync-slash" /></template>
