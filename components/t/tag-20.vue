<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m2yxnrbti.css';
import '../../css/s/suyzx0beu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="m2yxnrbti"/><path class="suyzx0beu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:tag-20" /></template>
