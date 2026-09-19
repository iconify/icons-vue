<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jcl2dvbkk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="jcl2dvbkk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:whatsappalt" /></template>
