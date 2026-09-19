<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/snfofybnw.css';
import '../../css/b/bxmkebcbg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="snfofybnw"/><path class="bxmkebcbg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:message-alt-minus" /></template>
