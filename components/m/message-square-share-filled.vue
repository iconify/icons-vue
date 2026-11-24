<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qqu28rbuo.css';
import '../../css/j/jsfqiobhi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qqu28rbuo"/><path class="jsfqiobhi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:message-square-share-filled" /></template>
