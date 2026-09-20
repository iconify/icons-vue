<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eiy3sgb5z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eiy3sgb5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:pointer-question" /></template>
