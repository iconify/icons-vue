<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tx3-ah38a.css';
import '../../css/g/gjzjcyb6i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b tx3-ah38a"/><path class="b gjzjcyb6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:shape-rotate-cw" /></template>
