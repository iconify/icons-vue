<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zxox9ob4e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zxox9ob4e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:social-facebook" /></template>
