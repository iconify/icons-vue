<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rhjm4i6en.css';
import '../../css/m/mol_khq9h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rhjm4i6en"/><path clip-rule="evenodd" class="mol_khq9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:microwave-filled" /></template>
