<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qovs41bxq.css';
import '../../css/b/bmffqxcpw.css';
import '../../css/p/p-xw0w-5p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qovs41bxq"/><path class="bmffqxcpw"/><path class="p-xw0w-5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:wand-20" /></template>
