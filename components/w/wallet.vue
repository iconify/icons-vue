<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c9uymhwhj.css';
import '../../css/v/veovc1s6o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c9uymhwhj"/><path class="veovc1s6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:wallet" /></template>
