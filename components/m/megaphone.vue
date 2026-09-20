<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kfh34bycq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kfh34bycq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:megaphone" /></template>
