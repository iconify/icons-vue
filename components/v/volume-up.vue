<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/il2cuacvw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"top":-3};
const content = `<path class="il2cuacvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:volume-up" /></template>
