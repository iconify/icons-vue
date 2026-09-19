<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r_n7dobql.css';
import '../../css/m/m6gu448fr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r_n7dobql"/><path class="m6gu448fr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:rotate-cw-30-filled" /></template>
