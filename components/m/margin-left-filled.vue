<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ze3zlmbzw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ze3zlmbzw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:margin-left-filled" /></template>
