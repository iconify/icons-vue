<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mg9fendhi.css';
import '../../css/p/pzsltxbqg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mg9fendhi"/><path class="pzsltxbqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:wallet" /></template>
