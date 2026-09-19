<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/joxurxbtg.css';
import '../../css/p/p0sim5hxc.css';
import '../../css/c/cfmfgyb-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="joxurxbtg"/><path clip-rule="evenodd" class="p0sim5hxc"/><path clip-rule="evenodd" class="cfmfgyb-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cuida:translate-outline" /></template>
