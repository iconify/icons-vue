<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kav2cebon.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kav2cebon"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:octagon-minus-filled" /></template>
