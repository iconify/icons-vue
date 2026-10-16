<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n3tl7xpsr.css';
import '../../css/t/t8tzpkb5n.css';
import '../../css/a/a196s7ber.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="n3tl7xpsr"/><path class="t8tzpkb5n"/><path class="a196s7ber"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:safety-boot-20" /></template>
