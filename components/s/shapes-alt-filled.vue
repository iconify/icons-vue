<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/apfcrhlku.css';
import '../../css/g/g-6i4by5o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="apfcrhlku"/><rect class="g-6i4by5o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:shapes-alt-filled" /></template>
