<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b9p8olbup.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="b9p8olbup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:playpause" /></template>
