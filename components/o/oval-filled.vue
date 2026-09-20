<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xu6r57b3c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xu6r57b3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:oval-filled" /></template>
