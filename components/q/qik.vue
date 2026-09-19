<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hlzckxbnt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":440,"height":488};
const content = `<path class="hlzckxbnt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:qik" /></template>
