<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tld_fzzem.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tld_fzzem"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:yen-diamond-solid" /></template>
