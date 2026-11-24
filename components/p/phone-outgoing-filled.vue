<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hpyifib8k.css';
import '../../css/a/ay19o3lge.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hpyifib8k"/><path class="ay19o3lge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:phone-outgoing-filled" /></template>
