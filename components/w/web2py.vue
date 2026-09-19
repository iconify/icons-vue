<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/puo-53u7k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="puo-53u7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:web2py" /></template>
