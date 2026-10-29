<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nt3a1iz-v.css';
import '../../css/h/huhyiebpf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nt3a1iz-v"/><path class="huhyiebpf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:navigation" /></template>
