<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hbd9vjcah.css';
import '../../css/o/o559_525r.css';
import '../../css/c/cn051wbje.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hbd9vjcah"/><path class="o559_525r"/><path class="cn051wbje"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:thumbs-down-sharp" /></template>
