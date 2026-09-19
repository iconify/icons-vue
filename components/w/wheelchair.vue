<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a8gd9bcgb.css';
import '../../css/e/ewb21wbfu.css';
import '../../css/b/b8pd5uezq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="a8gd9bcgb"/><circle class="ewb21wbfu"/><path class="b8pd5uezq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:wheelchair" /></template>
