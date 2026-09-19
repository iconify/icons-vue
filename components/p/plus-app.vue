<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q5vm1ymhp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="q5vm1ymhp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:plus-app" /></template>
