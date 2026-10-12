<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kw9a5abfk.css';
import '../../css/k/kqu7g8lpe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="kw9a5abfk"/><path class="kqu7g8lpe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:phone-waves-fill-20" /></template>
