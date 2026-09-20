<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ti42oubap.css';
import '../../css/r/rjaz92bbn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":351.46,"height":258.785,"left":35.188,"top":31.512};
const content = `<path class="ti42oubap"/><path class="rjaz92bbn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:nvidia-light" /></template>
