<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dh_wizjii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dh_wizjii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:square-letter-e-filled" /></template>
