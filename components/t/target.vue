<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i2k121bbm.css';
import '../../css/a/aok3b9cse.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i2k121bbm"/><path class="aok3b9cse"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:target" /></template>
