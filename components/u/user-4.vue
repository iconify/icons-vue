<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ae0kc3blq.css';
import '../../css/r/r8w6x7bjy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path clip-rule="evenodd" class="ae0kc3blq"/><path class="r8w6x7bjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:user-4" /></template>
