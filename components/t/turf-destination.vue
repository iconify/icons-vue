<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bywkocsmn.css';
import '../../css/t/tvvbqnhhg.css';
import '../../css/c/credxixyt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="bywkocsmn"/><circle class="tvvbqnhhg"/><path class="credxixyt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="geo:turf-destination" /></template>
