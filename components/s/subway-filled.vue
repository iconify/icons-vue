<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o36p4fb4z.css';
import '../../css/c/cj_6u2bea.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o36p4fb4z"/><path class="cj_6u2bea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:subway-filled" /></template>
