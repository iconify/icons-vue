<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hpyifib8k.css';
import '../../css/h/hj55octgf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hpyifib8k"/><path class="hj55octgf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:phone-missed-filled" /></template>
