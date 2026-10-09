<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b1l6u8egw.css';
import '../../css/w/w96urvnks.css';
import '../../css/m/m-4vi5jcl.css';
import '../../css/k/kj6hglb4g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="b1l6u8egw"/><path class="w96urvnks"/><path class="m-4vi5jcl"/><path class="kj6hglb4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:solar-array-sun-20" /></template>
