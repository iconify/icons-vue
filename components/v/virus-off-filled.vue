<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dsfup6hkd.css';
import '../../css/m/mwsqe_7mb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dsfup6hkd"/><path class="mwsqe_7mb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:virus-off-filled" /></template>
