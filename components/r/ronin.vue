<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bha5ecbwn.css';
import '../../css/p/p078on3jf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bha5ecbwn"/><path clip-rule="evenodd" class="p078on3jf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:ronin" /></template>
