<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hz6sozb5l.css';
import '../../css/d/d6s6-cbpf.css';
import '../../css/c/cqty_1bzi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hz6sozb5l"/><path class="d6s6-cbpf"/><path class="cqty_1bzi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:person-remove-outline" /></template>
