<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sul3pg2pb.css';
import '../../css/x/x-sy1absj.css';
import '../../css/n/n8uzvhbvq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="sul3pg2pb"/><path class="x-sy1absj"/><path class="n8uzvhbvq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:rss" /></template>
