<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eg4id_vou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="eg4id_vou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:percent-badge-solid" /></template>
