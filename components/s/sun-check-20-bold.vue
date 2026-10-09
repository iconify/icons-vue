<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ci7qqaciu.css';
import '../../css/a/aqsnv9bnd.css';
import '../../css/q/qvksvzdwk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ci7qqaciu"/><path class="aqsnv9bnd"/><path class="qvksvzdwk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:sun-check-20-bold" /></template>
