<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kr5qu_bcy.css';
import '../../css/d/dnb3cibqn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kr5qu_bcy"/><path clip-rule="evenodd" class="dnb3cibqn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:playing-cards-filled" /></template>
