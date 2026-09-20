<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zi8hcxn_c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zi8hcxn_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:plus-minus" /></template>
