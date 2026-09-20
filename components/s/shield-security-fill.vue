<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gnr0hmy3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gnr0hmy3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:shield-security-fill" /></template>
