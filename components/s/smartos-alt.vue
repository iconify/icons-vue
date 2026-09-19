<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mdyau_yns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mdyau_yns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:smartos-alt" /></template>
