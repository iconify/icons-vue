<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r3j0fwjec.css';
import '../../css/o/ou4giibdr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r3j0fwjec"/><path class="ou4giibdr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:volume-2-filled" /></template>
