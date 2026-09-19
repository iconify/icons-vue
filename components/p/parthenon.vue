<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mv4wiccsr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1025};
const content = `<path class="mv4wiccsr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:parthenon" /></template>
