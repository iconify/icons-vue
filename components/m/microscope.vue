<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dnoxl_b1j.css';
import '../../css/z/z_k3pkzmr.css';
import '../../css/z/z48vg0cpf.css';
import '../../css/z/z6d695bur.css';
import '../../css/b/b_nvdob_p.css';
import '../../css/z/zgawo1bkz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dnoxl_b1j"/><path class="z_k3pkzmr"/><path class="z48vg0cpf"/><path class="z6d695bur"/><path class="b_nvdob_p"/><path class="zgawo1bkz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:microscope" /></template>
