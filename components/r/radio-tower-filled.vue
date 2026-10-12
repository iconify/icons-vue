<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l4-njpbvj.css';
import '../../css/i/ity428tdo.css';
import '../../css/p/pembsco1c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l4-njpbvj"/><path class="ity428tdo"/><path class="pembsco1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:radio-tower-filled" /></template>
