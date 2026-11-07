<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/newyx7bgu.css';
import '../../css/l/lzldlfb0v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="newyx7bgu"/><path class="lzldlfb0v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:podcast-bold-duotone" /></template>
