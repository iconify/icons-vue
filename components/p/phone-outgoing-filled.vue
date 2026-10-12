<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hpyifib8k.css';
import '../../css/j/j-btr2exy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hpyifib8k"/><path class="j-btr2exy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:phone-outgoing-filled" /></template>
