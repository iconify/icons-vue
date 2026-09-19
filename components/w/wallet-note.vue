<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sjccsx91c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sjccsx91c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:wallet-note" /></template>
