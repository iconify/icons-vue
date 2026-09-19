<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p4evc5b5u.css';
import '../../css/t/tmkh_-28d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="p4evc5b5u"/><path class="tmkh_-28d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:moon-night" /></template>
