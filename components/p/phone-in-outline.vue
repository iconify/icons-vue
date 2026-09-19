<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gaiu7u7ew.css';
import '../../css/l/lh649k1wk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gaiu7u7ew"/><path class="lh649k1wk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:phone-in-outline" /></template>
