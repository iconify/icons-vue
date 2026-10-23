<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a17nokbxk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a17nokbxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:screw-filled" /></template>
