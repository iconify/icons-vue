<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cwfj1li-o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cwfj1li-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:star-filled" /></template>
