<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gc25bjpgv.css';
import '../../css/k/ksajmtbwp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path clip-rule="evenodd" class="gc25bjpgv"/><path class="ksajmtbwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:text-format-remove" /></template>
