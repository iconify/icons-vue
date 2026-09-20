<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qt7il2bsc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qt7il2bsc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:monad" /></template>
