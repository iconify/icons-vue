<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sfo80ubkp.css';
import '../../css/j/jx6xceb7r.css';
import '../../css/b/b_flqm05r.css';
import '../../css/h/ho9tv7fwi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="sfo80ubkp"/><path class="jx6xceb7r"/><path class="b_flqm05r"/><path class="ho9tv7fwi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:photodiode-20-bold" /></template>
