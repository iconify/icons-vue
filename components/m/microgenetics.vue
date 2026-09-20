<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/py3qm5roi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="py3qm5roi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:microgenetics" /></template>
