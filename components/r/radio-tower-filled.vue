<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/di0sukb5w.css';
import '../../css/h/ho6ftnbun.css';
import '../../css/p/pembsco1c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="di0sukb5w"/><path class="ho6ftnbun"/><path class="pembsco1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:radio-tower-filled" /></template>
