<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bcyvurbju.css';
import '../../css/j/jd64cjbns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="bcyvurbju"/><path class="jd64cjbns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:woman-sharp" /></template>
