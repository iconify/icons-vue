<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGwKMZ2bvI)" class="qcx4zdpsw"/><path fill="url(#SVGAluWoMIc)" class="roekc7-sd"/><path fill="url(#SVGPtGkgrKP)" class="k_a-rlsad"/><defs><linearGradient id="SVGwKMZ2bvI" x1="11.991" x2="11.991" y1="3" y2="21" gradientUnits="userSpaceOnUse"><stop class="p3o77ib8v"/><stop offset="1" class="uzjifdb_b"/></linearGradient><linearGradient id="SVGAluWoMIc" x1="11.999" x2="11.999" y1="20.999" y2="2.999" gradientUnits="userSpaceOnUse"><stop class="vff3dac-e"/><stop offset="1" class="slmn9ubzx"/></linearGradient><linearGradient id="SVGPtGkgrKP" x1="12.056" x2="12.056" y1="3" y2="21" gradientUnits="userSpaceOnUse"><stop class="ju23pobot"/><stop offset="1" class="p46ni5-va"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:sfund" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.ju23pobot {
  stop-color: var(--svg-color--45cffb, #45cffb);
}

.k_a-rlsad {
  d: path("M11.758 21c-1.469-1.355-3.68-5.04-.806-8.962l1.1-1.445c.61-.824 1.373-3.102.023-4.969c-.166-.227-1.274-1-2.094-.19l-.104.12l.104-.115L12.193 3c1.502 1.336 3.828 4.917 1.123 8.56l-1.421 1.837c-.516.735-1.246 2.795 0 5.192c.289.436 1.421.673 2.364-.379z");
}

.p3o77ib8v {
  stop-color: var(--svg-color--986ef8, #986ef8);
}

.p46ni5-va {
  stop-color: var(--svg-color--9e68fc, #9e68fc);
}

.qcx4zdpsw {
  d: path("m9.096 6.387l3.126-3.34l.128 2.108c-.464.483-1.966 1.895-3.69 4.16c-1.535 2.012-.062 4.58 1.061 5.503v1.871c-.734-.398-2.07-.933-3.05-3.353c-1.213-2.984.956-5.249 2.425-6.95");
}

.roekc7-sd {
  d: path("M14.983 17.456L11.847 20.8l-.123-2.108c.464-.488 1.848-1.999 3.695-4.159c1.516-1.781 0-4.666-1.061-5.267V7.414c.73.397 1.96.776 2.946 3.197c1.208 2.984-.71 5.485-2.321 6.845");
}

.slmn9ubzx {
  stop-color: var(--svg-color--8651e7, #8651e7);
}

.uzjifdb_b {
  stop-color: var(--svg-color--4592e6, #4592e6);
}

.vff3dac-e {
  stop-color: var(--svg-color--3cd7fe, #3cd7fe);
}

</style>
