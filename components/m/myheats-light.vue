<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qz15a5bue.css';
import '../../css/h/hvvzmxb9t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qz15a5bue"/><path class="hvvzmxb9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:myheats-light" /></template>
