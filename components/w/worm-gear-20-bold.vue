<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bryv9-bhw.css';
import '../../css/k/kb7fl3kua.css';
import '../../css/g/gd-r2cbpj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="bryv9-bhw"/><path class="kb7fl3kua"/><path class="gd-r2cbpj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:worm-gear-20-bold" /></template>
