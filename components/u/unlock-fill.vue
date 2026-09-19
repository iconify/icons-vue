<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c818x0b4f.css';
import '../../css/h/h8vkg4b-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="c818x0b4f"/><path class="h8vkg4b-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:unlock-fill" /></template>
