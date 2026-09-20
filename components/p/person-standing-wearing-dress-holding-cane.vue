<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t_tjqsbzx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="t_tjqsbzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-standing-wearing-dress-holding-cane" /></template>
