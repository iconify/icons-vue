<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kq_288ohw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kq_288ohw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:version" /></template>
