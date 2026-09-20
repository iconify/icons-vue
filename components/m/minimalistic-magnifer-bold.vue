<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/csocnccks.css';
import '../../css/l/llqf1f1jk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="csocnccks"/><path clip-rule="evenodd" class="llqf1f1jk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:minimalistic-magnifer-bold" /></template>
