<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ifpa9nduq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ifpa9nduq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:medal2" /></template>
