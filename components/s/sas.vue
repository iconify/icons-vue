<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v9cgckbcm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":342,"height":512};
const content = `<path class="v9cgckbcm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:sas" /></template>
