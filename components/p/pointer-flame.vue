<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qed2t9bdv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qed2t9bdv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:pointer-flame" /></template>
