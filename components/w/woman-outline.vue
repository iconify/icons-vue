<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h5hel5j6j.css';
import '../../css/f/f5kqw9b6l.css';
import '../../css/o/o0lqhvmmi.css';
import '../../css/k/k8brvnbck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h5hel5j6j"/><path class="f5kqw9b6l"/><circle class="o0lqhvmmi"/><path class="k8brvnbck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:woman-outline" /></template>
