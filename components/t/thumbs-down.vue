<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k9c5i0b2v.css';
import '../../css/o/o559_525r.css';
import '../../css/c/cn051wbje.css';
import '../../css/v/v4uhdgb-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="k9c5i0b2v"/><path class="o559_525r"/><path class="cn051wbje"/><path class="v4uhdgb-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:thumbs-down" /></template>
