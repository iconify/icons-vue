<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gjj4o5bfd.css';
import '../../css/z/zuoex-dnf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gjj4o5bfd"/><path class="zuoex-dnf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:minus-square-full" /></template>
