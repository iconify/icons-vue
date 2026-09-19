<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o0vdt7_4y.css';
import '../../css/z/zgf90ac7u.css';
import '../../css/v/vaqg0pb0u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="o0vdt7_4y"/><path class="zgf90ac7u"/><path class="vaqg0pb0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:mobile-twotone" /></template>
