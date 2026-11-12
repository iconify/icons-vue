<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fhb5m-zip.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fhb5m-zip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:table-code" /></template>
