<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGVpdIhdcN)" class="l6pq54n9a"/><path fill="url(#SVGVpdIhdcN)" class="t157osnvu"/><path class="em4be1dsh"/><path class="ivfb-pbej"/><defs><linearGradient id="SVGVpdIhdcN" x1="12" x2="12" y1="8.5" y2="21" gradientUnits="userSpaceOnUse"><stop class="d-74wm_fu"/><stop offset="1" class="suky3tblz"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:voxel" /></template>
<style>
.d-74wm_fu {
  stop-color: var(--svg-color--0e2c5e, #0e2c5e);
}

.em4be1dsh {
  fill: var(--svg-color--f5c700, #f5c700);
  d: path("M12 6.78L9 8l-.5-.5c.584-.3 1.88-.88 2.405-1.055c.524-.18.594-1.53.594-2.195c-.175-.18-.25-.39-.25-.5c0-.535.53-.75.75-.75z");
}

.ft5dv1b6b {
  fill: none;
}

.ivfb-pbej {
  fill: var(--svg-color--efbb1e, #efbb1e);
  d: path("M12 6.78L15 8l.5-.5a27 27 0 0 0-2.405-1.055c-.526-.18-.596-1.53-.596-2.195c.175-.18.25-.39.25-.5c0-.535-.53-.75-.75-.75z");
}

.l6pq54n9a {
  d: path("m10.625 15.775l.55-7.275c-1.65 0-3.835 1.515-4.675 2.275v3.75C7.05 17.7 10.4 20.165 12 21v-2.615c-.46-.27-1.375-1.93-1.375-2.61");
}

.suky3tblz {
  stop-color: var(--svg-color--16448f, #16448f);
}

.t157osnvu {
  d: path("m13.375 15.775l-.55-7.275c1.65 0 3.835 1.515 4.675 2.275v3.75C16.95 17.7 13.6 20.165 12 21v-2.615c.46-.27 1.375-1.93 1.375-2.61");
}

</style>
