<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tmbdk2b0r.css';
import '../../css/p/pmzg9nbdr.css';
import '../../css/x/x5lbktbtf.css';
import '../../css/c/cccmkiv6b.css';
import '../../css/s/sifs2853s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<circle class="tmbdk2b0r"/><path class="pmzg9nbdr"/><circle class="x5lbktbtf"/><path class="cccmkiv6b"/><path class="sifs2853s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:vmdk-disk" /></template>
