<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGHyAJeeQb)" clip-rule="evenodd" class="p89q1acvv"/><path fill="url(#SVGGXfYQ0SQ)" clip-rule="evenodd" class="g-kb6fb5q"/><defs><linearGradient id="SVGHyAJeeQb" x1="18.77" x2="9.104" y1="6.666" y2="17.079" gradientUnits="userSpaceOnUse"><stop class="p5a2awbap"/><stop offset="1" class="dr75gcb5m"/></linearGradient><linearGradient id="SVGGXfYQ0SQ" x1="18.771" x2="9.105" y1="6.668" y2="17.081" gradientUnits="userSpaceOnUse"><stop class="p5a2awbap"/><stop offset="1" class="dr75gcb5m"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:max" /></template>
<style>
.dr75gcb5m {
  stop-color: var(--svg-color--9cce7e, #9cce7e);
}

.ft5dv1b6b {
  fill: none;
}

.g-kb6fb5q {
  fill-rule: evenodd;
  d: path("M8.797 18.153a3.805 3.805 0 0 1-.346-5.395l5.813-6.57a3.875 3.875 0 0 1 5.433-.341a3.81 3.81 0 0 1 1.095 4.106c-.164.475-.42.913-.754 1.289l-5.808 6.57a3.875 3.875 0 0 1-5.433.34m2.217-.805c.947 0 1.72-.763 1.72-1.706c0-.942-.773-1.705-1.72-1.705s-1.72.763-1.72 1.705s.773 1.706 1.72 1.706m8.09-8.432a2.131 2.131 0 1 1-4.262 0a2.131 2.131 0 0 1 4.263 0");
}

.p5a2awbap {
  stop-color: var(--svg-color--0cb5ad, #0cb5ad);
}

.p89q1acvv {
  fill-rule: evenodd;
  d: path("M12.946 17.9a3.21 3.21 0 0 1-4.495-.062l-4.557-4.647a3.154 3.154 0 0 1 .062-4.462a3.21 3.21 0 0 1 4.5.062l4.556 4.647a3.127 3.127 0 0 1-.061 4.462zm-7.105-6.376a.947.947 0 1 0 0-1.894a.947.947 0 0 0 0 1.894m6.892 4.117c0 .942-.772 1.705-1.72 1.705c-.947 0-1.72-.763-1.72-1.706c0-.942.773-1.705 1.72-1.705c.948 0 1.72.763 1.72 1.705");
}

</style>
