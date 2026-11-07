<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jj9upir-e.css';
import '../../css/y/yjxhxvben.css';
import '../../css/y/yz0ivnopn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jj9upir-e"/><path class="yjxhxvben"/><path clip-rule="evenodd" class="yz0ivnopn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:star-ring-bold-duotone" /></template>
