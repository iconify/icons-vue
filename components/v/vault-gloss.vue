<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gt9m4abwz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gt9m4abwz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:vault-gloss" /></template>
