<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k8nfwjaam.css';
import '../../css/v/vgzcqeb4l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="k8nfwjaam"/><path class="vgzcqeb4l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:vuestorefront" /></template>
