<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zx93v9xsw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zx93v9xsw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:paperclip-rounded-2-broken" /></template>
