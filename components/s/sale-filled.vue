<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xlutzvs1e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xlutzvs1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:sale-filled" /></template>
