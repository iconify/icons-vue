<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/loy5a9xpv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="loy5a9xpv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:ocean" /></template>
