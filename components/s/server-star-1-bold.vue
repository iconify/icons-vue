<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ojjc2sbvn.css';
import '../../css/o/oh7nkob3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ojjc2sbvn"/><path class="oh7nkob3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:server-star-1-bold" /></template>
