<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xcqdxjb3l.css';
import '../../css/s/sk9-dtbox.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xcqdxjb3l"/><path clip-rule="evenodd" class="sk9-dtbox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:question-32" /></template>
